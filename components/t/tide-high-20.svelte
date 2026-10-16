<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-93wacki.css';
import '../../css/p/p5711fb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b-93wacki"/><path class="p5711fb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tide-high-20" {...props}></Icon>
