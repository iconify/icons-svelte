<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh1s3ih8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hh1s3ih8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:shield-plus" {...props}></Icon>
