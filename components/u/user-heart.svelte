<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-10rbyac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-10rbyac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-heart" {...props}></Icon>
