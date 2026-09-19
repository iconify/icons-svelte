<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdxn-ef5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="bdxn-ef5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:signal-alt-slash" {...props}></Icon>
