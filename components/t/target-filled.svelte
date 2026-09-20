<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhkscqhiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fhkscqhiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:target-filled" {...props}></Icon>
