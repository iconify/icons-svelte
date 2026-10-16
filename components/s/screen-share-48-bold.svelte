<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw2mmrfxt.css';
import '../../css/p/phox42bnd.css';
import '../../css/q/qh1-sxi6o.css';
import '../../css/k/kn0wafhon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kw2mmrfxt"/><path class="phox42bnd"/><path class="qh1-sxi6o"/><path class="kn0wafhon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:screen-share-48-bold" {...props}></Icon>
