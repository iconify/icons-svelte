<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gppv4vhln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gppv4vhln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-2-fill" {...props}></Icon>
