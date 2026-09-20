<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujg4rdbof.css';
import '../../css/b/br8qj_t-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ujg4rdbof"/><path class="br8qj_t-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scrobblex" {...props}></Icon>
