<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja584fb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ja584fb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:suse" {...props}></Icon>
