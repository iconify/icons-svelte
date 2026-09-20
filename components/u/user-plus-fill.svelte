<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o030v6xup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o030v6xup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:user-plus-fill" {...props}></Icon>
