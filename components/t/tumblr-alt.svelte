<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avd0ktjgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avd0ktjgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:tumblr-alt" {...props}></Icon>
