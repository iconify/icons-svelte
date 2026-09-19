<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsblh3ttn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tsblh3ttn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:stroller" {...props}></Icon>
