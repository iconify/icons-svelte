<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fioatobyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fioatobyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:shrink-diagonal-light" {...props}></Icon>
