<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k18nmbumu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k18nmbumu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:videocamera-record-bold" {...props}></Icon>
