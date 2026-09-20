<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttx7m2byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ttx7m2byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:rss-feed-logo-block" {...props}></Icon>
