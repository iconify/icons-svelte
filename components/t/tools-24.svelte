<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc1atjb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc1atjb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:tools-24" {...props}></Icon>
