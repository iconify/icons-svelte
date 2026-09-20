<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjqyefo-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fjqyefo-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:section-divider-light" {...props}></Icon>
