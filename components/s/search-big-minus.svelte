<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd6gj6bbb.css';
import '../../css/o/o17bt0bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pd6gj6bbb"/><path class="o17bt0bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-big-minus" {...props}></Icon>
