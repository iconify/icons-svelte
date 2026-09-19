<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0grz6btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="x0grz6btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:sina-weibo-small" {...props}></Icon>
