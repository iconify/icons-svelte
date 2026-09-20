<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd-hh9b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pd-hh9b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-arrow-down" {...props}></Icon>
