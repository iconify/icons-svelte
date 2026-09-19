<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udnvig89x.css';
import '../../css/m/mj6sbgtse.css';
import '../../css/y/y9ompvb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="udnvig89x"/><path class="mj6sbgtse"/><path class="y9ompvb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:speakercancellation" {...props}></Icon>
