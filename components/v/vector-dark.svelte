<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bio4dy26q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bio4dy26q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vector-dark" {...props}></Icon>
