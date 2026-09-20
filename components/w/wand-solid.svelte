<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1eucru7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="q1eucru7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wand-solid" {...props}></Icon>
