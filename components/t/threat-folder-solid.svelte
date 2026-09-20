<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp04zqb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gp04zqb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:threat-folder-solid" {...props}></Icon>
