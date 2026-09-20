<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sunee7f3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sunee7f3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sign-language" {...props}></Icon>
