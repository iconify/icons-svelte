<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sacl49i0j.css';
import '../../css/f/fv1pvlf1q.css';
import '../../css/q/qi3bd4p2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="sacl49i0j"/><path class="fv1pvlf1q"/><path class="qi3bd4p2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:rss-right" {...props}></Icon>
