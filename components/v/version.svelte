<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq_288ohw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kq_288ohw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:version" {...props}></Icon>
