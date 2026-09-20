<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yipit4bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yipit4bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:square-full" {...props}></Icon>
