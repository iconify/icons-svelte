<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3a-qlz6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e3a-qlz6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:social-twitter-light" {...props}></Icon>
