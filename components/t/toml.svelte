<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zofucd4sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zofucd4sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:toml" {...props}></Icon>
