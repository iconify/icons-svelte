<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa_2v2l-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa_2v2l-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:times-light" {...props}></Icon>
