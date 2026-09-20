<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqws7db-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="aqws7db-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:shopping-bag-alt" {...props}></Icon>
