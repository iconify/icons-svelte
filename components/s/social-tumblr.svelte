<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao59tsqbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ao59tsqbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-tumblr" {...props}></Icon>
