<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rinuwhlnp.css';
import '../../css/w/wtbqjwbif.css';
import '../../css/c/c4bl7z6jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="rinuwhlnp"><path class="wtbqjwbif"/><path class="c4bl7z6jp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:vest" {...props}></Icon>
