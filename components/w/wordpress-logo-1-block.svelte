<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgsltwbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hgsltwbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:wordpress-logo-1-block" {...props}></Icon>
