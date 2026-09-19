<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfd8llbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mfd8llbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:speech-language-therapy" {...props}></Icon>
