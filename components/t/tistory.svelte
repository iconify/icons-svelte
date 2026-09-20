<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzs57dbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzs57dbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tistory" {...props}></Icon>
