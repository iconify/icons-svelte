<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy-bghb3k.css';
import '../../css/v/v8a8hebya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<ellipse class="sy-bghb3k"/><path class="v8a8hebya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:skateboarding" {...props}></Icon>
