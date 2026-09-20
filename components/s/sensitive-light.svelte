<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pplbo7oar.css';
import '../../css/c/c8aj1-b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pplbo7oar"/><path class="c8aj1-b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:sensitive-light" {...props}></Icon>
