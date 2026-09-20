<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uicqk6jbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uicqk6jbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:windows" {...props}></Icon>
