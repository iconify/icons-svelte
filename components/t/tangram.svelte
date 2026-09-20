<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk8rsab9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gk8rsab9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tangram" {...props}></Icon>
