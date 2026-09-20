<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4hucqbjw.css';
import '../../css/q/qurvgrb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4hucqbjw"/><path class="qurvgrb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vanar" {...props}></Icon>
