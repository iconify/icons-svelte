<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfc8g4bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfc8g4bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:settings-fill" {...props}></Icon>
