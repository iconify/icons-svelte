<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiqehwiew.css';
import '../../css/w/we_txpblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kiqehwiew"/><path class="we_txpblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:shield-user-light" {...props}></Icon>
