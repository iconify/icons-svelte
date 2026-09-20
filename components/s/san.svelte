<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrnllbmrd.css';
import '../../css/n/ncz4lgb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mrnllbmrd"/><path class="ncz4lgb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:san" {...props}></Icon>
