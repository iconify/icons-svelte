<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9y477w0i.css';
import '../../css/e/en0qu8tuo.css';
import '../../css/a/attm18beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="n9y477w0i"/><path class="en0qu8tuo"/><path class="attm18beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-close-bold-duotone" {...props}></Icon>
