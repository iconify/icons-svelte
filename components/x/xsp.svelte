<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gafgfqgjb.css';
import '../../css/l/lnil9jecv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gafgfqgjb"/><path class="lnil9jecv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xsp" {...props}></Icon>
