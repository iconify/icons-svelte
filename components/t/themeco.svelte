<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjjw42d6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kjjw42d6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:themeco" {...props}></Icon>
