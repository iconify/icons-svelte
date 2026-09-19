<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-uqoxsah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q-uqoxsah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:six" {...props}></Icon>
