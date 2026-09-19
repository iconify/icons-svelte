<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5rwtnb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5rwtnb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:victoria-m" {...props}></Icon>
