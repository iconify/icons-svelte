<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfodpcckw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lfodpcckw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:woo" {...props}></Icon>
