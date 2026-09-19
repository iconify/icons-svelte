<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0f2lhr2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":897,"height":1024};
const content = `<path class="b0f2lhr2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sim" {...props}></Icon>
