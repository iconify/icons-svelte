<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0stm7b7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0stm7b7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:table-columns-split" {...props}></Icon>
