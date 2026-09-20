<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfs6bob9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hfs6bob9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:virustotal-logo-block" {...props}></Icon>
