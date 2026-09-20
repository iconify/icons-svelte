<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb_7qobvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rb_7qobvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:table-fill" {...props}></Icon>
