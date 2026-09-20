<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go8c5qwvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go8c5qwvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:rugby" {...props}></Icon>
