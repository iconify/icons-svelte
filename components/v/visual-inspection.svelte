<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjbc43igg.css';
import '../../css/a/a_barob7i.css';
import '../../css/k/kffkq4b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjbc43igg"/><path class="a_barob7i"/><path class="kffkq4b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:visual-inspection" {...props}></Icon>
