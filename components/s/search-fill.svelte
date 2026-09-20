<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nywdskjzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nywdskjzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:search-fill" {...props}></Icon>
