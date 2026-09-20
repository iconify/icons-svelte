<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c21ih15aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c21ih15aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:star3" {...props}></Icon>
