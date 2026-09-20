<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olznt6bba.css';
import '../../css/a/augpk_bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olznt6bba"/><path class="augpk_bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:search-minus" {...props}></Icon>
