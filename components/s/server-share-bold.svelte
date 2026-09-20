<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9-uq4bby.css';
import '../../css/t/txip2qdzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9-uq4bby"/><path class="txip2qdzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:server-share-bold" {...props}></Icon>
