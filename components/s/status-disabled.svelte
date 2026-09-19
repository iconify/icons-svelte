<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e32245upq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e32245upq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:status-disabled" {...props}></Icon>
