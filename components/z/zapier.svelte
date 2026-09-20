<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jik0o4btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jik0o4btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:zapier" {...props}></Icon>
