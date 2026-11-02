<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smbh6-igf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smbh6-igf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sugar-coated-haws-line" {...props}></Icon>
