<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziblf8w-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziblf8w-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smiley-devil-outline" {...props}></Icon>
