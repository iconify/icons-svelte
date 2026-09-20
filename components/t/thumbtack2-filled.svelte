<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edjn9ccsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edjn9ccsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:thumbtack2-filled" {...props}></Icon>
