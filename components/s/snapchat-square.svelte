<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8gre2b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8gre2b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:snapchat-square" {...props}></Icon>
