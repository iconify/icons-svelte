<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab-pd873z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ab-pd873z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:yelp-fill" {...props}></Icon>
