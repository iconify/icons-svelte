<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzm7f0b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzm7f0b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:themodelsresource" {...props}></Icon>
