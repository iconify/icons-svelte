<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb7-g2b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nb7-g2b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:sticky-note-plus" {...props}></Icon>
