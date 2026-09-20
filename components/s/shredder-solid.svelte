<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj2v5po7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aj2v5po7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shredder-solid" {...props}></Icon>
