<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq7duib7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq7duib7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:settings-fill" {...props}></Icon>
