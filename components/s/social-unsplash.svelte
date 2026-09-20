<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p06tlqbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p06tlqbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:social-unsplash" {...props}></Icon>
