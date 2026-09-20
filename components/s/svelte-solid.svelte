<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjpa3xbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="vjpa3xbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:svelte-solid" {...props}></Icon>
