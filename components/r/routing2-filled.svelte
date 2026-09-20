<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq5lxvu6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq5lxvu6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:routing2-filled" {...props}></Icon>
