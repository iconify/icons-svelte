<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6tcv5b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="l6tcv5b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:shredder" {...props}></Icon>
