<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpgx4vb3u.css';
import '../../css/b/bdkmogxxu.css';
import '../../css/d/d2rrvbcjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gpgx4vb3u"/><path class="bdkmogxxu"/><path class="d2rrvbcjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:run" {...props}></Icon>
