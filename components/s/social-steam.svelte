<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n91xzbc8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n91xzbc8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-steam" {...props}></Icon>
