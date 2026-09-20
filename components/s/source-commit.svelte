<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go8lz-9sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go8lz-9sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:source-commit" {...props}></Icon>
