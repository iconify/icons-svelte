<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcb9t62hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcb9t62hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:spinner-dotted" {...props}></Icon>
