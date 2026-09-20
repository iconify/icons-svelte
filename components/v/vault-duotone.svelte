<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3x5_inum.css';
import '../../css/w/wx5lbcbct.css';
import '../../css/a/afas8h87o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3x5_inum"/><path class="wx5lbcbct"/><path class="afas8h87o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:vault-duotone" {...props}></Icon>
