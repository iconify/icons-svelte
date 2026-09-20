<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp7n27b5q.css';
import '../../css/q/q5eclkb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp7n27b5q"/><path clip-rule="evenodd" class="q5eclkb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:social-unsplash-duotone" {...props}></Icon>
