<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1hgb6bzy.css';
import '../../css/f/fj3ryr4ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1hgb6bzy"/><path class="fj3ryr4ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:swimming-fill" {...props}></Icon>
