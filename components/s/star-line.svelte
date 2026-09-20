<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7j9fhbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7j9fhbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:star-line" {...props}></Icon>
