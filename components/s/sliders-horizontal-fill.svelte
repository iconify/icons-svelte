<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9be7jb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9be7jb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sliders-horizontal-fill" {...props}></Icon>
