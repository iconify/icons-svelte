<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aux903b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aux903b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wikidocs-light" {...props}></Icon>
