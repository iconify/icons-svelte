<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shy0p6bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shy0p6bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:undo-alt" {...props}></Icon>
