<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz50wxbre.css';
import '../../css/z/zh9lxxd8p.css';
import '../../css/j/jzsn4fblp.css';
import '../../css/a/a5nz24eur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pz50wxbre"/><path class="zh9lxxd8p"/><path class="jzsn4fblp"/><path class="a5nz24eur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xbackbone" {...props}></Icon>
