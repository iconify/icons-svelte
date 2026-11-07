<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7bc-4bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7bc-4bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:unread-broken" {...props}></Icon>
