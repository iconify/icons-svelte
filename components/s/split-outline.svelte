<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs-zd6s9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bs-zd6s9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:split-outline" {...props}></Icon>
