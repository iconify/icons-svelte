<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7fzjmd8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7fzjmd8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:saopaulometro" {...props}></Icon>
