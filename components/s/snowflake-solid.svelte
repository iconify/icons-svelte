<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbne24udz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bbne24udz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:snowflake-solid" {...props}></Icon>
