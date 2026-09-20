<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq7dm-fht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq7dm-fht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:user-share" {...props}></Icon>
