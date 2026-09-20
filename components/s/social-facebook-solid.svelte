<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/najg4qvqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="najg4qvqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:social-facebook-solid" {...props}></Icon>
