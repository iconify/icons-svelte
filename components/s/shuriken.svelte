<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ognnid77f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ognnid77f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:shuriken" {...props}></Icon>
