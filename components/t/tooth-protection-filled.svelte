<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2681jbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g2681jbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-protection-filled" {...props}></Icon>
