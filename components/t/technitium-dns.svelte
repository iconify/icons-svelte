<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht-0wk75v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ht-0wk75v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:technitium-dns" {...props}></Icon>
