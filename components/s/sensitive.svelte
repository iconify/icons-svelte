<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi_ym-bhd.css';
import '../../css/d/d6kw7zb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi_ym-bhd"/><path class="d6kw7zb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:sensitive" {...props}></Icon>
