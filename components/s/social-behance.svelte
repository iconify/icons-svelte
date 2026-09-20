<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg34m8bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sg34m8bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-behance" {...props}></Icon>
