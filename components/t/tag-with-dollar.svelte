<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-02oj49z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q-02oj49z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tag-with-dollar" {...props}></Icon>
