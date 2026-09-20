<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq_pn4bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="wq_pn4bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:wifi" {...props}></Icon>
