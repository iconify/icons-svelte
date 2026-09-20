<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw8zzfb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw8zzfb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:runkeeper" {...props}></Icon>
