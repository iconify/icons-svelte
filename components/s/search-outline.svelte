<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj0yhl7gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aj0yhl7gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:search-outline" {...props}></Icon>
