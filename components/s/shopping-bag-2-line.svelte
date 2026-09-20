<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sixwq45kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sixwq45kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shopping-bag-2-line" {...props}></Icon>
