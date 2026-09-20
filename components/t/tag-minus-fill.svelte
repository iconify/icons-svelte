<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7ixe7qvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7ixe7qvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:tag-minus-fill" {...props}></Icon>
