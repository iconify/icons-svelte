<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skjyq2bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skjyq2bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:umbrella-closed-variant" {...props}></Icon>
