<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayjea6ayf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayjea6ayf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:xi" {...props}></Icon>
