<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v27938bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v27938bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:store-alt-filled" {...props}></Icon>
