<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg_s3ib6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rg_s3ib6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:text-strikethrough" {...props}></Icon>
