<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl15a80lp.css';
import '../../css/b/b-i2932jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nl15a80lp"/><path class="b-i2932jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-clock-20" {...props}></Icon>
